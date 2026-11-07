<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrtv4rb5l.css';
import '../../css/b/bidl9_apl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtv4rb5l"/><path clip-rule="evenodd" class="bidl9_apl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-audio-circle-bold" {...props}></Icon>
