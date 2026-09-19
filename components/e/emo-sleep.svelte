<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iktdgbbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":888,"height":1000};
const content = `<path class="iktdgbbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-sleep" {...props}></Icon>
