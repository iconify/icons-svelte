<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veat5ojxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="veat5ojxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:caret-right-filled" {...props}></Icon>
