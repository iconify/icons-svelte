<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkqy2hbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkqy2hbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:information-circle-solid" {...props}></Icon>
