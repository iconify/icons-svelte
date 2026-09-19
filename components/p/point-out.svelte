<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_n_7bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="za_n_7bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:point-out" {...props}></Icon>
