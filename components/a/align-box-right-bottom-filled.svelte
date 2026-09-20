<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwtkn5bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwtkn5bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-right-bottom-filled" {...props}></Icon>
