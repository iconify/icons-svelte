<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7xqisbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-7};
const content = `<path class="e7xqisbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-down-left" {...props}></Icon>
