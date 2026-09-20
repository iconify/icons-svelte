<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp_t65bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp_t65bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:apw" {...props}></Icon>
