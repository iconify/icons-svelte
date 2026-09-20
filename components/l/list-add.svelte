<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6433eekj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v6433eekj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:list-add" {...props}></Icon>
