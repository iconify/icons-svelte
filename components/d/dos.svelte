<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3r5xob4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3r5xob4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dos" {...props}></Icon>
