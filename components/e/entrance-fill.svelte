<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gutkbgbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gutkbgbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:entrance-fill" {...props}></Icon>
