<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jblp27bhe.css';
import '../../css/h/hoh3fpbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jblp27bhe"/><path class="hoh3fpbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bug-20" {...props}></Icon>
