<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz6ri2bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz6ri2bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:function-fill-round" {...props}></Icon>
