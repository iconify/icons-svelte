<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke9bzzbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":870,"height":1000};
const content = `<path class="ke9bzzbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-grin" {...props}></Icon>
