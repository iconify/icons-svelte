<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf9l8pb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kf9l8pb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:question-small-outline" {...props}></Icon>
