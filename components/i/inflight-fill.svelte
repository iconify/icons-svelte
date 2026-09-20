<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8whxzl8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8whxzl8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:inflight-fill" {...props}></Icon>
