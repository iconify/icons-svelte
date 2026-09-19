<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkwfr08ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fkwfr08ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:forgejo" {...props}></Icon>
