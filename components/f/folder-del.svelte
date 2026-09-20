<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3nypc2-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3nypc2-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-del" {...props}></Icon>
