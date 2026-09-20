<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgb8wkb_n.css';
import '../../css/v/vpvf7rb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgb8wkb_n"/><path class="vpvf7rb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:qanx" {...props}></Icon>
