<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faez23tsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="faez23tsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-descending-align-right" {...props}></Icon>
