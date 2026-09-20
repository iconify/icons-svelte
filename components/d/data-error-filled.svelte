<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnuozhkls.css';
import '../../css/o/ob_wxib3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="bnuozhkls"/><path class="ob_wxib3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:data-error-filled" {...props}></Icon>
