<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meu77l_qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meu77l_qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:cnn-logo-block" {...props}></Icon>
