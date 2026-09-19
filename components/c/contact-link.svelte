<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko6hr-8xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ko6hr-8xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:contact-link" {...props}></Icon>
