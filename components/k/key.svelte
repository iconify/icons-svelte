<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwof9_rjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwof9_rjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:key" {...props}></Icon>
