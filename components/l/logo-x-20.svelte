<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik425sgmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ik425sgmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-x-20" {...props}></Icon>
