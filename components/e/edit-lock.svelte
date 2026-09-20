<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdd69vbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gdd69vbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:edit-lock" {...props}></Icon>
