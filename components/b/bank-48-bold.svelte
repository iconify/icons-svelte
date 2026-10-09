<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0t44tbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a0t44tbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bank-48-bold" {...props}></Icon>
