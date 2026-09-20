<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn5chso7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="pn5chso7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-circle-up-left" {...props}></Icon>
