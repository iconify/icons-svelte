<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmwufopie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmwufopie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-square-detail" {...props}></Icon>
