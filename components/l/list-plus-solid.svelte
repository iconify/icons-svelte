<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh2ohabkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh2ohabkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-plus-solid" {...props}></Icon>
