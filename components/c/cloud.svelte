<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osn1-qbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osn1-qbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cloud" {...props}></Icon>
