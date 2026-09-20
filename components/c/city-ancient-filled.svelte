<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v78162bxf.css';
import '../../css/g/gxoekfbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v78162bxf"/><path class="gxoekfbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-ancient-filled" {...props}></Icon>
