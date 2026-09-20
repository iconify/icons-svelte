<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdufc8b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdufc8b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:message-alt-fill" {...props}></Icon>
