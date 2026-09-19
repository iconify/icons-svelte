<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5uu06nhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5uu06nhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:aruba" {...props}></Icon>
