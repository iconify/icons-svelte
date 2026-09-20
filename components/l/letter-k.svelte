<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3v-bh0qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3v-bh0qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k" {...props}></Icon>
