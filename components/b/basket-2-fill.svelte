<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9hd6vbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9hd6vbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:basket-2-fill" {...props}></Icon>
