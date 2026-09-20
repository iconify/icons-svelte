<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n08kipbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n08kipbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:leaf-light" {...props}></Icon>
