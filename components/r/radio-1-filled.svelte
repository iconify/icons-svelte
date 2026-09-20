<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndmfzni2t.css';
import '../../css/u/u32-2c2je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndmfzni2t"/><path class="u32-2c2je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:radio-1-filled" {...props}></Icon>
