<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa7fvljmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa7fvljmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:dial-pad" {...props}></Icon>
