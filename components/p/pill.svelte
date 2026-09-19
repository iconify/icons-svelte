<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh38_cbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh38_cbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pill" {...props}></Icon>
