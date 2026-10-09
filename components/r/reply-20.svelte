<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gypgls1dd.css';
import '../../css/e/ems1_nb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gypgls1dd"/><path class="ems1_nb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reply-20" {...props}></Icon>
