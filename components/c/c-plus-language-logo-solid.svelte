<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbfuw4bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbfuw4bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:c-plus-language-logo-solid" {...props}></Icon>
