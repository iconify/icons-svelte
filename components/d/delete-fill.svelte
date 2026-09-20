<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sht37ysff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sht37ysff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-fill" {...props}></Icon>
