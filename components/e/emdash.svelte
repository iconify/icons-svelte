<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik_ga42_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":643,"height":614};
const content = `<path class="ik_ga42_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:emdash" {...props}></Icon>
