<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cln-37cul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cln-37cul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:clipboard" {...props}></Icon>
