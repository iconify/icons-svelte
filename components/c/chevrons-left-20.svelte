<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_7y3qb_r.css';
import '../../css/h/hrdk82bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j_7y3qb_r"/><path class="hrdk82bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-left-20" {...props}></Icon>
