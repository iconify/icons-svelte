<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/artiuobsj.css';
import '../../css/u/u815dwbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="artiuobsj"/><path class="u815dwbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:a-frame-20" {...props}></Icon>
