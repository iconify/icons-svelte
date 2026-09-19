<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iam11pbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iam11pbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-document" {...props}></Icon>
