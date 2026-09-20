<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrwacn2yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hrwacn2yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:babyroom" {...props}></Icon>
