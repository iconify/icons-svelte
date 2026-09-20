<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj-8hfbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yj-8hfbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bloglovin-logo-block" {...props}></Icon>
