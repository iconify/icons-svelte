<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/p/pp4ihlbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><circle class="pp4ihlbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:radio" {...props}></Icon>
