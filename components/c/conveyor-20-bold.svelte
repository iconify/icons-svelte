<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kekwewb2q.css';
import '../../css/a/a52o52b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kekwewb2q"/><path class="a52o52b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:conveyor-20-bold" {...props}></Icon>
