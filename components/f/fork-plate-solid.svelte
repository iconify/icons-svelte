<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np1ww71-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="np1ww71-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fork-plate-solid" {...props}></Icon>
