<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igxjfccxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="igxjfccxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:people-fill-20" {...props}></Icon>
