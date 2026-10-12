<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj2-olrwi.css';
import '../../css/i/ii3oq8bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bj2-olrwi"/><path class="ii3oq8bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-arrow-left-fill-20" {...props}></Icon>
