<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr0z36_3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fr0z36_3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:indent-less-16" {...props}></Icon>
