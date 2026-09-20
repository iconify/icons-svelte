<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li2u5xh7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="li2u5xh7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:padlock-square-2-solid" {...props}></Icon>
