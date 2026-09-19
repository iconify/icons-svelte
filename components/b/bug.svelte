<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr197o85d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr197o85d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:bug" {...props}></Icon>
