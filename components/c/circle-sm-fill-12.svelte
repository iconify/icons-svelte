<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdxmgm20z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="kdxmgm20z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-sm-fill-12" {...props}></Icon>
