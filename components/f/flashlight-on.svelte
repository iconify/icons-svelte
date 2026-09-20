<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knzx8abpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knzx8abpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flashlight-on" {...props}></Icon>
