<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbpe4x0tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbpe4x0tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:folder-fill" {...props}></Icon>
