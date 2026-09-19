<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s65hwzmez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s65hwzmez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-descending-align-left-arrow-up" {...props}></Icon>
