<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtxtpbb-v.css';
import '../../css/w/wrzlzeb2x.css';
import '../../css/j/j3iwccb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wtxtpbb-v"/><path class="wrzlzeb2x"/><path class="j3iwccb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ore-48" {...props}></Icon>
