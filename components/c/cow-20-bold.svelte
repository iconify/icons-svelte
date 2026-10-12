<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gli25bb3i.css';
import '../../css/j/jpkklnhzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gli25bb3i"/><path class="jpkklnhzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cow-20-bold" {...props}></Icon>
