<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjfc7kb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pjfc7kb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bookmark-solid" {...props}></Icon>
