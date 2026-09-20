<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgilk566a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-8};
const content = `<path class="tgilk566a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-down" {...props}></Icon>
