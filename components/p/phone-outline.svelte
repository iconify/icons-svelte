<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7z1bxusg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7z1bxusg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:phone-outline" {...props}></Icon>
