<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3gfemb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3gfemb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-code-filled" {...props}></Icon>
