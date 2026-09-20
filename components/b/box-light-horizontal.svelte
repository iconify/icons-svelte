<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acka1kbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="acka1kbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal" {...props}></Icon>
