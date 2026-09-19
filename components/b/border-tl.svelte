<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqq4bzftk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqq4bzftk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:border-tl" {...props}></Icon>
