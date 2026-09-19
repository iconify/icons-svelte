<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqpak4kov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fqpak4kov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:algolia" {...props}></Icon>
