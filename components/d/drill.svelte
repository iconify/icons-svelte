<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3f-3lbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3f-3lbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:drill" {...props}></Icon>
