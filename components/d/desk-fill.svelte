<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8cp9tb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8cp9tb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:desk-fill" {...props}></Icon>
