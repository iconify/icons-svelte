<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfbn8ab0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfbn8ab0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notification-solid" {...props}></Icon>
