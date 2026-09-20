<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onqq3ib-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="onqq3ib-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-sa" {...props}></Icon>
