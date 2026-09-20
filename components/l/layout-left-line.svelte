<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjb99vb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjb99vb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-left-line" {...props}></Icon>
