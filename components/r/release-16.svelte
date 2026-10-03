<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abepz8bal.css';
import '../../css/h/h2b5tt5ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="abepz8bal"/><path class="h2b5tt5ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:release-16" {...props}></Icon>
