<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp0ronb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0ronb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:01dotai" {...props}></Icon>
