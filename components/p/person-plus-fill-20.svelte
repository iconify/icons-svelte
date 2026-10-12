<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klg708bis.css';
import '../../css/n/nib5s-byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="klg708bis"/><path class="nib5s-byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-plus-fill-20" {...props}></Icon>
