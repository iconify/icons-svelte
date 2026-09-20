<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnwaqn2lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnwaqn2lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane-departure" {...props}></Icon>
