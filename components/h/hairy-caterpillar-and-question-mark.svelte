<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuaurdb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kuaurdb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hairy-caterpillar-and-question-mark" {...props}></Icon>
