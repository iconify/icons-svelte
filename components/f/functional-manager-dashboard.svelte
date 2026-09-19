<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvad9gncn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zvad9gncn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:functional-manager-dashboard" {...props}></Icon>
