<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn65x6g0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn65x6g0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:github-fill-round" {...props}></Icon>
