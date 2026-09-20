<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5d9x7bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5d9x7bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:itchdotio" {...props}></Icon>
