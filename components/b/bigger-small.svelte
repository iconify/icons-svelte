<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdcjrw-cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jdcjrw-cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bigger-small" {...props}></Icon>
