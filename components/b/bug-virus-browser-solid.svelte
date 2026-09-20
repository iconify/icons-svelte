<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju2t91bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju2t91bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bug-virus-browser-solid" {...props}></Icon>
