<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo--jxzmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jo--jxzmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:bookmark" {...props}></Icon>
