<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3agib3wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3agib3wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-back-outline" {...props}></Icon>
