<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_6gxrb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p_6gxrb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:menu" {...props}></Icon>
