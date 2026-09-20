<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em7xvwbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="em7xvwbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:invisible-2-flat" {...props}></Icon>
