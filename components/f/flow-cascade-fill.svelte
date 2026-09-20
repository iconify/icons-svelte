<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohx0-hb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohx0-hb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-cascade-fill" {...props}></Icon>
