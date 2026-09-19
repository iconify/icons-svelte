<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaivl163v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kaivl163v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:comments" {...props}></Icon>
