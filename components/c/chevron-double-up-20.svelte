<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whfucbber.css';
import '../../css/v/v1vmo492j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="whfucbber"/><path class="v1vmo492j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-up-20" {...props}></Icon>
