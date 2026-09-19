<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9b-07nxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a9b-07nxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:lightning-circle-filled" {...props}></Icon>
