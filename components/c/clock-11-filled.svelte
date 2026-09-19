<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te5-__5uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te5-__5uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-11-filled" {...props}></Icon>
