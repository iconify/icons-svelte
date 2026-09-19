<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1wyy2ehi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1wyy2ehi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:elipsis-h" {...props}></Icon>
