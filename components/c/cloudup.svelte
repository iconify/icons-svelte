<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3sj-aczu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s3sj-aczu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:cloudup" {...props}></Icon>
