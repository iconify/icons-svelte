<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paqxdte2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="paqxdte2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:question-in-circle" {...props}></Icon>
