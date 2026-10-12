<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj2-olrwi.css';
import '../../css/z/z-s_bkbrl.css';
import '../../css/u/uus2tq10l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bj2-olrwi"/><path class="z-s_bkbrl"/><path class="uus2tq10l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-arrow-left-stroke-20" {...props}></Icon>
