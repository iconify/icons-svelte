<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqus3ibdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqus3ibdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:desktop-chat-solid" {...props}></Icon>
