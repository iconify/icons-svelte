<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2mf_7bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t2mf_7bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-ordered-48-bold" {...props}></Icon>
