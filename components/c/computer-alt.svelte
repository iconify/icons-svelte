<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0s3xrbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="n0s3xrbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:computer-alt" {...props}></Icon>
