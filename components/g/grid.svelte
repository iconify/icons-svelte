<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2s3nidsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="h2s3nidsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:grid" {...props}></Icon>
