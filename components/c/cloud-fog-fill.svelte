<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi6hjcbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bi6hjcbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-fog-fill" {...props}></Icon>
