<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aowkw-b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aowkw-b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:divider-line-outline" {...props}></Icon>
