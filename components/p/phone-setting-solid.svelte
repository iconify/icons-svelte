<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmbrdxb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmbrdxb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-setting-solid" {...props}></Icon>
