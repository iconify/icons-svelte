<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5u5fxb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5u5fxb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:memory" {...props}></Icon>
