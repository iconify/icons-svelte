<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkkd7rb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkkd7rb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-diagonal" {...props}></Icon>
