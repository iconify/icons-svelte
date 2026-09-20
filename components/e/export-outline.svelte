<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0whs1-mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0whs1-mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:export-outline" {...props}></Icon>
