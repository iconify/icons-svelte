<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t96l2flpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t96l2flpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:plane" {...props}></Icon>
