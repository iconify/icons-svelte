<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v25h3yxjz.css';
import '../../css/y/yh5ytlqor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v25h3yxjz"/><path class="yh5ytlqor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:history-bold-duotone" {...props}></Icon>
