<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysgd0luzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysgd0luzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-lines-fill" {...props}></Icon>
