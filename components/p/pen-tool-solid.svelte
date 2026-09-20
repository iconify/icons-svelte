<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te54cpbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te54cpbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pen-tool-solid" {...props}></Icon>
