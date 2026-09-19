<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckg3ubbyx.css';
import '../../css/g/gcn7qhbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckg3ubbyx"/><path clip-rule="evenodd" class="gcn7qhbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:comment-block-outline" {...props}></Icon>
