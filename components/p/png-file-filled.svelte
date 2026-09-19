<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqwu_c0kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqwu_c0kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:png-file-filled" {...props}></Icon>
