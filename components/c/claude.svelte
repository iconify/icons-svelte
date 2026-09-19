<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_44m9bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w_44m9bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:claude" {...props}></Icon>
