<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz2u3n6qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz2u3n6qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cyborg-solid" {...props}></Icon>
