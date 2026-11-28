<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-2r3ac9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2r3ac9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fast-forward" {...props}></Icon>
