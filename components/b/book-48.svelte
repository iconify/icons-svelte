<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajqks0bek.css';
import '../../css/o/ohhmv4blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ajqks0bek"/><path class="ohhmv4blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-48" {...props}></Icon>
