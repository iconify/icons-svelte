<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw7wwe3lc.css';
import '../../css/o/ovk3-rb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kw7wwe3lc"/><path class="ovk3-rb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-remix" {...props}></Icon>
