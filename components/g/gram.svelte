<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8_28dbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8_28dbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gram" {...props}></Icon>
