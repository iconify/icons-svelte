<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgtah-2oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cgtah-2oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:eye-optic-remix" {...props}></Icon>
