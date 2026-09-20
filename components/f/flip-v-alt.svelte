<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0e3a7b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0e3a7b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:flip-v-alt" {...props}></Icon>
