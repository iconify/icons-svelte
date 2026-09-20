<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go41ypbnd.css';
import '../../css/q/quv6-_b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go41ypbnd"/><path class="quv6-_b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-add-filled" {...props}></Icon>
