<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv6e5ubox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv6e5ubox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:edit-exposure" {...props}></Icon>
