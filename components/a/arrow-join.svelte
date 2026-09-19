<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmsox0bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmsox0bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-join" {...props}></Icon>
