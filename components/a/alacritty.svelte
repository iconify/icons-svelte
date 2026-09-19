<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au9or3-rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":449,"height":512};
const content = `<path class="au9or3-rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:alacritty" {...props}></Icon>
