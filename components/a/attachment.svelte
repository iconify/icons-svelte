<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knp3hqltq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":472};
const content = `<path class="knp3hqltq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:attachment" {...props}></Icon>
