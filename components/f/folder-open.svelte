<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn1v9ob2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn1v9ob2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:folder-open" {...props}></Icon>
