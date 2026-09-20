<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omlq569zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omlq569zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:parabola" {...props}></Icon>
