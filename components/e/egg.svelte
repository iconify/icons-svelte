<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udnf14b2t.css';
import '../../css/x/xz4g601-d.css';
import '../../css/d/ddxxdn1gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udnf14b2t wm-k"/><path class="wm-k xz4g601-d"/><path class="ddxxdn1gm wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:egg" {...props}></Icon>
