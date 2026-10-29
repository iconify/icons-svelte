<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9go7hbsg.css';
import '../../css/v/vaz59h5au.css';
import '../../css/q/q22873scb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9go7hbsg wm-a"/><path class="vaz59h5au wm-k"/><path class="q22873scb wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:pin" {...props}></Icon>
