<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z90c49l7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z90c49l7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bar-chart" {...props}></Icon>
