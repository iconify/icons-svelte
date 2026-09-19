<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft1d7lbyz.css';
import '../../css/w/w2fc8uq2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft1d7lbyz"/><path class="w2fc8uq2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cycling-filled" {...props}></Icon>
