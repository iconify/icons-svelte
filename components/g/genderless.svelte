<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lin5v0buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lin5v0buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:genderless" {...props}></Icon>
