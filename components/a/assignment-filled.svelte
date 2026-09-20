<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzu8gmcad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzu8gmcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:assignment-filled" {...props}></Icon>
