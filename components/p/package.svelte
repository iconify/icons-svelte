<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5u0e5usu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5u0e5usu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:package" {...props}></Icon>
