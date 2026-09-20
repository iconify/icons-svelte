<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1s3hgbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1s3hgbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-left-waves-solid" {...props}></Icon>
