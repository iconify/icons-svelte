<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhzh0gbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhzh0gbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fork-fill" {...props}></Icon>
