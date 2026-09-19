<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se8-wzb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se8-wzb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-threat" {...props}></Icon>
