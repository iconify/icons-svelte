<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz44lebrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz44lebrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:install" {...props}></Icon>
