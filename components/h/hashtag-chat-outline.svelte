<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_vd_y58s.css';
import '../../css/j/jvqlzyq-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_vd_y58s"/><path clip-rule="evenodd" class="jvqlzyq-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-chat-outline" {...props}></Icon>
