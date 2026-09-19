<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq4ep8a-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq4ep8a-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-cancel" {...props}></Icon>
