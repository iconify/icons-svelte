<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svx0lxokl.css';
import '../../css/d/dgfy8elcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary svx0lxokl"/><path class="dgfy8elcu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-right-duo" {...props}></Icon>
