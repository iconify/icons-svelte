<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt-bdj62o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt-bdj62o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paster-fill" {...props}></Icon>
