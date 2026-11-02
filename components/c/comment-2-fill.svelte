<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr1a8xbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr1a8xbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:comment-2-fill" {...props}></Icon>
