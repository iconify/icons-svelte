<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl3kfub2g.css';
import '../../css/q/quvshjb7w.css';
import '../../css/g/g4ik5wbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dl3kfub2g"/><path class="quvshjb7w"/><path class="g4ik5wbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-20" {...props}></Icon>
