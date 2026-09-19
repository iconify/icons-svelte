<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo961jb7c.css';
import '../../css/k/kit0fd8ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo961jb7c"/><path class="kit0fd8ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-triangle" {...props}></Icon>
