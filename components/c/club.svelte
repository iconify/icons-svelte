<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4uhf6e_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4uhf6e_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:club" {...props}></Icon>
