<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by7nze-ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="by7nze-ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-no-access-outline" {...props}></Icon>
