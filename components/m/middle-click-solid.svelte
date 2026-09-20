<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnfs7ie5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnfs7ie5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:middle-click-solid" {...props}></Icon>
