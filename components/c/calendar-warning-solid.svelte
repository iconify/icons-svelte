<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzho5zdvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzho5zdvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:calendar-warning-solid" {...props}></Icon>
