<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl26lxpjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hl26lxpjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:restart-fill" {...props}></Icon>
