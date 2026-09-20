<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuosp9q_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuosp9q_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-lucene" {...props}></Icon>
