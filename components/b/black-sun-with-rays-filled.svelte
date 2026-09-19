<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0097eb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b0097eb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-sun-with-rays-filled" {...props}></Icon>
