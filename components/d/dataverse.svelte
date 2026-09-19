<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1u67tbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="b1u67tbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:dataverse" {...props}></Icon>
