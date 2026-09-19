<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f07u9n9jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f07u9n9jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:paper-clip" {...props}></Icon>
