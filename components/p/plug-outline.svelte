<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz9atvzrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cz9atvzrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:plug-outline" {...props}></Icon>
