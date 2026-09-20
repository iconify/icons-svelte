<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8qg1bfqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8qg1bfqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-left" {...props}></Icon>
