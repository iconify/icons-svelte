<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvlfz5cod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvlfz5cod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-money-filled" {...props}></Icon>
