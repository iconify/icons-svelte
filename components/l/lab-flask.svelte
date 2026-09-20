<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kil35zu_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kil35zu_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:lab-flask" {...props}></Icon>
