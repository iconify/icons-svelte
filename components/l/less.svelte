<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3wj-lbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s3wj-lbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:less" {...props}></Icon>
