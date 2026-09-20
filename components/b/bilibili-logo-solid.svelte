<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6og42bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6og42bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bilibili-logo-solid" {...props}></Icon>
