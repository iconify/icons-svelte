<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq2xs6b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jq2xs6b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:memes-comment-reply-solid" {...props}></Icon>
