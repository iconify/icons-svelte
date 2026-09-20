<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qodun26ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qodun26ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:horizontal-toggle-button-remix" {...props}></Icon>
