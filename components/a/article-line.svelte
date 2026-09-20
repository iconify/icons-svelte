<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5llrzbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5llrzbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:article-line" {...props}></Icon>
