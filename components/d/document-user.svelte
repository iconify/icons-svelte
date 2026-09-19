<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/polvqg_iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="polvqg_iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-user" {...props}></Icon>
