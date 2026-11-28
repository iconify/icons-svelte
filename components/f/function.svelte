<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epde73bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epde73bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:function" {...props}></Icon>
