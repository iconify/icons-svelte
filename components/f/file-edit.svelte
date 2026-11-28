<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shhk2bz4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shhk2bz4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-edit" {...props}></Icon>
