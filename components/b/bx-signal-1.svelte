<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/useoh5bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="useoh5bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-signal-1" {...props}></Icon>
