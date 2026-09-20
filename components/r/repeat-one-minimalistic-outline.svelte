<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbla17bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbla17bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-minimalistic-outline" {...props}></Icon>
