<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvaxjbbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvaxjbbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-cauldron-filled" {...props}></Icon>
