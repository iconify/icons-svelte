<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi9y0klwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi9y0klwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-data-connection" {...props}></Icon>
