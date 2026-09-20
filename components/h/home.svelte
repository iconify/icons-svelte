<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un24y4bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="un24y4bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:home" {...props}></Icon>
