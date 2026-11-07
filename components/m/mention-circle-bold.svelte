<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6su4bex.css';
import '../../css/p/potfbbb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6su4bex"/><path clip-rule="evenodd" class="potfbbb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mention-circle-bold" {...props}></Icon>
