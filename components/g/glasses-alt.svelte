<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jal2fjbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jal2fjbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:glasses-alt" {...props}></Icon>
