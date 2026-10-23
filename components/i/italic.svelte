<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsb7o42fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsb7o42fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:italic" {...props}></Icon>
