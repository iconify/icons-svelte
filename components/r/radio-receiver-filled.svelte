<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqx-81tcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqx-81tcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radio-receiver-filled" {...props}></Icon>
