<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv9csh0_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv9csh0_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:object-group" {...props}></Icon>
