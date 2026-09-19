<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb5pocb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="vb5pocb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:boxing" {...props}></Icon>
