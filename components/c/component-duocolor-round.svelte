<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q08auabzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q08auabzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-duocolor-round" {...props}></Icon>
