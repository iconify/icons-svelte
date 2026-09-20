<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b01z6tb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b01z6tb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-check-sharp-fill" {...props}></Icon>
