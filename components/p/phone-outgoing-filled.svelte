<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd0rgtwak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pd0rgtwak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:phone-outgoing-filled" {...props}></Icon>
