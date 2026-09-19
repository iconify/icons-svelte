<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_taptxtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_taptxtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-drop-24px" {...props}></Icon>
