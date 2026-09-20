<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr8e64lzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr8e64lzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:home-check-solid" {...props}></Icon>
