<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dki-1w-8i.css';
import '../../css/z/z159gwm8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="dki-1w-8i"/><path class="z159gwm8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:china" {...props}></Icon>
