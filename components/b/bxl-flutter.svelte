<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m30vmp18n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m30vmp18n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-flutter" {...props}></Icon>
