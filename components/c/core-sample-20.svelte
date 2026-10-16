<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm7hjkbca.css';
import '../../css/b/bnwm9wbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fm7hjkbca"/><path class="bnwm9wbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:core-sample-20" {...props}></Icon>
