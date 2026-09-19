<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw621dqkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw621dqkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-solid" {...props}></Icon>
