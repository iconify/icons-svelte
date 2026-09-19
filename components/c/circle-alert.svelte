<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-xsgj-1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-xsgj-1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:circle-alert" {...props}></Icon>
