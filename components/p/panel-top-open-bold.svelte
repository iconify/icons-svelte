<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgaa_tbxh.css';
import '../../css/l/lzylfm93k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tgaa_tbxh"/><path class="lzylfm93k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-open-bold" {...props}></Icon>
