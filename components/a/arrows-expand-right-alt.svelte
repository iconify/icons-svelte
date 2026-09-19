<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my5e902_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my5e902_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-expand-right-alt" {...props}></Icon>
