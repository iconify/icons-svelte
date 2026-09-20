<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdvsb9bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pdvsb9bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:clipboard-list" {...props}></Icon>
