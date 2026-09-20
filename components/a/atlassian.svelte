<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi6eslbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi6eslbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:atlassian" {...props}></Icon>
