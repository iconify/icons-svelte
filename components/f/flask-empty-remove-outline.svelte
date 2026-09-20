<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt1668jtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt1668jtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-empty-remove-outline" {...props}></Icon>
