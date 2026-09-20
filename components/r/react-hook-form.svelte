<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjqq2vzds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjqq2vzds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:react-hook-form" {...props}></Icon>
