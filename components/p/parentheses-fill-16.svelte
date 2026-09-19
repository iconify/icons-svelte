<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w012ylbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w012ylbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:parentheses-fill-16" {...props}></Icon>
