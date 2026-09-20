<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dss7b2x8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dss7b2x8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:book-1-solid" {...props}></Icon>
