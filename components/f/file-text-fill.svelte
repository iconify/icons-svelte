<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxvkwlbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxvkwlbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:file-text-fill" {...props}></Icon>
