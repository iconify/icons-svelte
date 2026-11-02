<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crkw5cbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crkw5cbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anvil-fill" {...props}></Icon>
