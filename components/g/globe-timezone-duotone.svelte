<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en6b4kiau.css';
import '../../css/e/e7ebmvq0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en6b4kiau"/><path class="e7ebmvq0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:globe-timezone-duotone" {...props}></Icon>
