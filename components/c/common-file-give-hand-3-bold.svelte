<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5s1lcbbn.css';
import '../../css/d/dh2sg1pzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5s1lcbbn"/><path class="dh2sg1pzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-give-hand-3-bold" {...props}></Icon>
