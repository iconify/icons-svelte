<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot6w0-x5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot6w0-x5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:grid-line" {...props}></Icon>
