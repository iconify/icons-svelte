<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hst7d2bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hst7d2bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-skiing" {...props}></Icon>
