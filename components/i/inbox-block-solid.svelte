<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymftsyb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ymftsyb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-block-solid" {...props}></Icon>
