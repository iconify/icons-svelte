<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhx_p3bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="dhx_p3bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:plane-f" {...props}></Icon>
