<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6h_-78-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6h_-78-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cardano-ada-fill" {...props}></Icon>
