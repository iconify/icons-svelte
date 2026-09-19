<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-msuac5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1447,"height":1000};
const content = `<path class="k-msuac5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-thumbsup" {...props}></Icon>
