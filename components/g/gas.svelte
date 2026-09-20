<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp-tcp6en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp-tcp6en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gas" {...props}></Icon>
