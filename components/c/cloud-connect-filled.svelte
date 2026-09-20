<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf_np14xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cf_np14xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-connect-filled" {...props}></Icon>
