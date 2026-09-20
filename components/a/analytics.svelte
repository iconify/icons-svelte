<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5oc0ckag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5oc0ckag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:analytics" {...props}></Icon>
