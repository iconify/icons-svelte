<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emcctgb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="emcctgb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eye-closed-16" {...props}></Icon>
