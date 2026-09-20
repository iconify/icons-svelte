<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acxrv9d-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acxrv9d-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-7-fill" {...props}></Icon>
