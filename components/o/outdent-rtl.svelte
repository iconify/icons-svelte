<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfgrheeyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tfgrheeyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:outdent-rtl" {...props}></Icon>
