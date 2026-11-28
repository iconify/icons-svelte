<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfb3xu9nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfb3xu9nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-code-solid" {...props}></Icon>
