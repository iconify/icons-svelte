<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2pgv4bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16.2};
const content = `<path class="q2pgv4bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:altumptic" {...props}></Icon>
