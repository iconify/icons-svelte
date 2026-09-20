<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icp5hibgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="icp5hibgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-text" {...props}></Icon>
