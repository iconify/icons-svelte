<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3hxb00gr.css';
import '../../css/c/c2uptobfq.css';
import '../../css/n/nlryl0bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3hxb00gr"/><rect class="c2uptobfq"/><rect class="nlryl0bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-distribute-right-filled" {...props}></Icon>
