<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q19mp7b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q19mp7b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-descending-align-left" {...props}></Icon>
