<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3c-jwbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s3c-jwbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:pinterest-with-circle" {...props}></Icon>
