<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8anjebdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e8anjebdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pencil-small" {...props}></Icon>
