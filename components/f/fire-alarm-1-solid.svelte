<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auleabc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="auleabc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fire-alarm-1-solid" {...props}></Icon>
