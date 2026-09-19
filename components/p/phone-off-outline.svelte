<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf4v8xbuk.css';
import '../../css/v/v8r068qjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf4v8xbuk"/><path clip-rule="evenodd" class="v8r068qjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:phone-off-outline" {...props}></Icon>
