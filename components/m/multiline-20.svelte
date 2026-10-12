<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqcuttcnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqcuttcnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:multiline-20" {...props}></Icon>
