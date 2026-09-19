<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-spu3__s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-spu3__s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cloud-off" {...props}></Icon>
