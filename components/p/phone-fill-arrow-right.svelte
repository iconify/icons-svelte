<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lffxmfbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lffxmfbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-fill-arrow-right" {...props}></Icon>
