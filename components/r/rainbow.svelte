<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6zitzbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6zitzbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rainbow" {...props}></Icon>
