<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq-545bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq-545bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:code-duotone" {...props}></Icon>
