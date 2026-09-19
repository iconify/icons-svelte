<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egh3qukbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egh3qukbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:info-circle-solid" {...props}></Icon>
