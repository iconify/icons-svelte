<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcx3dab_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcx3dab_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cmdx" {...props}></Icon>
