<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbwic474o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbwic474o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:home-filled" {...props}></Icon>
