<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka7oo7zjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ka7oo7zjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-2-20" {...props}></Icon>
