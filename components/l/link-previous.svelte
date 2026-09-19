<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmb7g3bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmb7g3bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:link-previous" {...props}></Icon>
