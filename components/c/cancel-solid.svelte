<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahzihro8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ahzihro8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cancel-solid" {...props}></Icon>
