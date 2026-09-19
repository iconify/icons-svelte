<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m81es4bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m81es4bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-notes" {...props}></Icon>
