<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz3575bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nz3575bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cog-f" {...props}></Icon>
