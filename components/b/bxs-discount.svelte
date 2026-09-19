<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw--y17ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw--y17ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-discount" {...props}></Icon>
