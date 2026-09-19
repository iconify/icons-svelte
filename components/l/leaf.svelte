<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd_kc-9yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd_kc-9yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:leaf" {...props}></Icon>
