<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0dqwhbgb.css';
import '../../css/j/jzyuqzbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q0dqwhbgb"/><path class="jzyuqzbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-woman" {...props}></Icon>
