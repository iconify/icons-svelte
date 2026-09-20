<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kegiq1cwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kegiq1cwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-minus-filled" {...props}></Icon>
