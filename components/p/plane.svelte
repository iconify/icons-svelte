<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j35p42bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j35p42bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:plane" {...props}></Icon>
