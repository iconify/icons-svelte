<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x14s3jbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x14s3jbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-u-hexagon-solid" {...props}></Icon>
