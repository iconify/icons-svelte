<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhomschgd.css';
import '../../css/m/mz1wsz5pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhomschgd"/><path class="mz1wsz5pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:list-dropdown" {...props}></Icon>
