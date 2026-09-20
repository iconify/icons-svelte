<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amfc7iafx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amfc7iafx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:battery-low" {...props}></Icon>
