<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et_rd7bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999,"height":1000};
const content = `<path class="et_rd7bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-saint" {...props}></Icon>
