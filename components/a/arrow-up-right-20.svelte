<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7q9a2bck.css';
import '../../css/v/vzivax-kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f7q9a2bck"/><path class="vzivax-kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-right-20" {...props}></Icon>
