<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwt369onn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kwt369onn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:recycle-1-solid" {...props}></Icon>
