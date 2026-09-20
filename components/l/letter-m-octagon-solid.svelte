<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvz9emb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvz9emb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-m-octagon-solid" {...props}></Icon>
