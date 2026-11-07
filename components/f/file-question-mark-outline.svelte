<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4xmzwl1u.css';
import '../../css/x/x5se19b3w.css';
import '../../css/d/d25mwn3tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4xmzwl1u"/><path class="x5se19b3w"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-question-mark-outline" {...props}></Icon>
