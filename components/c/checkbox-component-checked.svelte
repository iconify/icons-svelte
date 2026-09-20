<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emf8wccme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emf8wccme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-component-checked" {...props}></Icon>
