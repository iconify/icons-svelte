<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_vdx0c-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="o_vdx0c-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-o" {...props}></Icon>
