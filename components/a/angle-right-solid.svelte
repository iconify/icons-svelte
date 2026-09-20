<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9hzgob4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9hzgob4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angle-right-solid" {...props}></Icon>
