<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifyp59bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifyp59bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-document" {...props}></Icon>
