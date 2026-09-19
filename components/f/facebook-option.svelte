<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2j799d2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2j799d2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:facebook-option" {...props}></Icon>
