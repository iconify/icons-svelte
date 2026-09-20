<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7lzhdc8k.css';
import '../../css/x/xg4x14bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7lzhdc8k"/><path class="xg4x14bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:multiply" {...props}></Icon>
