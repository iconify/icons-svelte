<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9m4smbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9m4smbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-left-fill" {...props}></Icon>
