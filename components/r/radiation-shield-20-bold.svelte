<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdw3vx8xp.css';
import '../../css/e/e1hzf-y8n.css';
import '../../css/f/fdsiutbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fdw3vx8xp"/><path class="e1hzf-y8n"/><path class="fdsiutbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiation-shield-20-bold" {...props}></Icon>
