<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlijh8b1j.css';
import '../../css/i/ii3oq8bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zlijh8b1j"/><path class="ii3oq8bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-arrow-right-fill-20" {...props}></Icon>
