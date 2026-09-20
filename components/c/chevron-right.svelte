<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npaeh2bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npaeh2bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chevron-right" {...props}></Icon>
