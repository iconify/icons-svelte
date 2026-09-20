<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8yq6e7ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8yq6e7ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:flow-merge" {...props}></Icon>
