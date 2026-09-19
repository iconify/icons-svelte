<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bna3i2b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bna3i2b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:question-circle-filled" {...props}></Icon>
