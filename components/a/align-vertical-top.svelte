<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uduo2dspc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="uduo2dspc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:align-vertical-top" {...props}></Icon>
