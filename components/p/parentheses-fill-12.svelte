<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ico7ur4iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ico7ur4iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:parentheses-fill-12" {...props}></Icon>
