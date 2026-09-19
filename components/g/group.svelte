<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4qcfbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_4qcfbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:group" {...props}></Icon>
