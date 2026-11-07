<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5c3_9bws.css';
import '../../css/t/twtz-lrju.css';
import '../../css/d/d25mwn3tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5c3_9bws"/><path class="twtz-lrju"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-terminal-outline" {...props}></Icon>
