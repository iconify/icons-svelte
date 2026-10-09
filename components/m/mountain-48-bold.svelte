<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz4dh6bfp.css';
import '../../css/e/ekqm_acki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jz4dh6bfp"/><path class="ekqm_acki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-48-bold" {...props}></Icon>
