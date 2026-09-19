<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enhmg-iip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enhmg-iip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:empty-circle" {...props}></Icon>
