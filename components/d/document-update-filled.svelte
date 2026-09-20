<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c83uesblw.css';
import '../../css/e/eyx20b7zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c83uesblw"/><path class="eyx20b7zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:document-update-filled" {...props}></Icon>
