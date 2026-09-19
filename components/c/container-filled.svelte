<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ruf9bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ruf9bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:container-filled" {...props}></Icon>
