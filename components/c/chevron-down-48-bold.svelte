<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7fn5abah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a7fn5abah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-down-48-bold" {...props}></Icon>
