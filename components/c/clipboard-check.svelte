<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzec2b5dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzec2b5dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-check" {...props}></Icon>
