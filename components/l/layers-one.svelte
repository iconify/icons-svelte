<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bey4ik7pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bey4ik7pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layers-one" {...props}></Icon>
