<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbpgcvbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbpgcvbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-circle-fill" {...props}></Icon>
