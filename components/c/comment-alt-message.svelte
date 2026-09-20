<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja86lubud.css';
import '../../css/s/s78ya2efd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja86lubud"/><path class="s78ya2efd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:comment-alt-message" {...props}></Icon>
