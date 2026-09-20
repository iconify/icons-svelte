<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmsrgab1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmsrgab1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linear-fill" {...props}></Icon>
