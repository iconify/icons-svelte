<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz-qdgbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-qdgbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chevron-left-outline" {...props}></Icon>
