<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg1ngf2io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg1ngf2io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-alt-filled" {...props}></Icon>
