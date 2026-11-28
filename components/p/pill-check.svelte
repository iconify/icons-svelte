<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-p5v55ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-p5v55ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pill-check" {...props}></Icon>
