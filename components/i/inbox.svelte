<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t07kclblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t07kclblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:inbox" {...props}></Icon>
