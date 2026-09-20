<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdv2mzb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdv2mzb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-down-box-fill" {...props}></Icon>
