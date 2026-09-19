<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5yg-621y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999,"height":1000};
const content = `<path class="b5yg-621y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-happy" {...props}></Icon>
