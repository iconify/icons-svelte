<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj43gzrlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj43gzrlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:link-unlink" {...props}></Icon>
