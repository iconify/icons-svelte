<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il0u59btn.css';
import '../../css/a/ai9whoirx.css';
import '../../css/a/av0edef4u.css';
import '../../css/l/lxpaeopia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il0u59btn"/><path class="ai9whoirx"/><path clip-rule="evenodd" class="av0edef4u"/><path clip-rule="evenodd" class="lxpaeopia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ethereum" {...props}></Icon>
