<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwxxqb3q.css';
import '../../css/o/oljgu37pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kkwxxqb3q"/><path class="oljgu37pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lithium-20-bold" {...props}></Icon>
