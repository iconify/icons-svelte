<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfx4sq3sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfx4sq3sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:link-duotone" {...props}></Icon>
