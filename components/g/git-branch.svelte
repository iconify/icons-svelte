<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-h5e-ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0-h5e-ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:git-branch" {...props}></Icon>
