<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noolj8nel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noolj8nel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:phone-5" {...props}></Icon>
