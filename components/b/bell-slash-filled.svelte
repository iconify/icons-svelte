<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apy5tabgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apy5tabgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bell-slash-filled" {...props}></Icon>
