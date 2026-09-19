<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijbr0i9jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ijbr0i9jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:duplicate-fill-12" {...props}></Icon>
