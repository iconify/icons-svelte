<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qglvkk1rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qglvkk1rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:in-progress" {...props}></Icon>
