<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbkc6ef-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dbkc6ef-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:question-mark" {...props}></Icon>
