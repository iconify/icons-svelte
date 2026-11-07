<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npl5ovbfu.css';
import '../../css/u/um_zvyb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npl5ovbfu"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-add-outline" {...props}></Icon>
