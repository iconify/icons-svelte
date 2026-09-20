<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbqh0mb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbqh0mb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:page-setting-solid" {...props}></Icon>
