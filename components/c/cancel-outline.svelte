<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynign8bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynign8bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:cancel-outline" {...props}></Icon>
