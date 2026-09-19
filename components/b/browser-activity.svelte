<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyues-25d.css';
import '../../css/l/l2z16-nsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyues-25d"/><path class="l2z16-nsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:browser-activity" {...props}></Icon>
