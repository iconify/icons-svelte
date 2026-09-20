<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr4511a7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr4511a7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:plus-outline" {...props}></Icon>
