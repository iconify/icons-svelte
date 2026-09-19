<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah5i6mb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah5i6mb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:clipboard" {...props}></Icon>
