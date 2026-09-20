<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snv6m8axw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="snv6m8axw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-outside" {...props}></Icon>
