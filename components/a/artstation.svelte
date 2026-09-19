<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqkq0jbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lqkq0jbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:artstation" {...props}></Icon>
