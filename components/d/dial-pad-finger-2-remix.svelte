<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibjh_vltj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibjh_vltj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dial-pad-finger-2-remix" {...props}></Icon>
