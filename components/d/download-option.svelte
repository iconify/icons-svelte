<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y87cecb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y87cecb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:download-option" {...props}></Icon>
