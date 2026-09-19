<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuh_jbm9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuh_jbm9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-rounded" {...props}></Icon>
