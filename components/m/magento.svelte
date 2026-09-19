<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpmse0ykx.css';
import '../../css/c/c77e_usuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="rpmse0ykx"/><path class="c77e_usuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:magento" {...props}></Icon>
