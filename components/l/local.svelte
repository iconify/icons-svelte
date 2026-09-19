<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfvekc1nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvekc1nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:local" {...props}></Icon>
