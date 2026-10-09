<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woejr8lkf.css';
import '../../css/h/h8ky2qf0l.css';
import '../../css/w/wbh530b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="woejr8lkf"/><path class="h8ky2qf0l"/><path class="wbh530b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sync-20-bold" {...props}></Icon>
