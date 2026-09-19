<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1w3o7btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1w3o7btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:caret-down-outline" {...props}></Icon>
