<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek3w6tbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ek3w6tbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:face-unhappy" {...props}></Icon>
