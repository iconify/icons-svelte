<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3lcuh0ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3lcuh0ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chevron-right-outline" {...props}></Icon>
