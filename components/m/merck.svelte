<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_inemb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_inemb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:merck" {...props}></Icon>
