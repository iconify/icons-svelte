<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m43v59bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m43v59bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:brightness-1-solid" {...props}></Icon>
