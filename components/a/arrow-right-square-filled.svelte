<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks6ph22qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks6ph22qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-square-filled" {...props}></Icon>
