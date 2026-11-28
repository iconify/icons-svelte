<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agd6jk7an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="agd6jk7an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:magnifying-glass-x-bold" {...props}></Icon>
