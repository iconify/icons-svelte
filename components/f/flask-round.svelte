<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dre4csbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b dre4csbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flask-round" {...props}></Icon>
