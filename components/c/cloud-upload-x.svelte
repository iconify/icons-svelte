<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r51afdcqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r51afdcqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-upload-x" {...props}></Icon>
