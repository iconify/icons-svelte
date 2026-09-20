<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1kkvib8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1kkvib8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward2-filled" {...props}></Icon>
