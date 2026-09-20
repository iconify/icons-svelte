<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2w4o88ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2w4o88ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-arrow-right-sharp" {...props}></Icon>
