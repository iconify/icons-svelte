<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ct_9bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1056,"height":1408};
const content = `<path class="t3ct_9bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:level-up" {...props}></Icon>
