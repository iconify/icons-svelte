<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crjb4ubpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crjb4ubpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:lastpass" {...props}></Icon>
