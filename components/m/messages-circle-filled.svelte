<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-p5e-beu.css';
import '../../css/o/oe8kfdbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-p5e-beu"/><path class="oe8kfdbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:messages-circle-filled" {...props}></Icon>
