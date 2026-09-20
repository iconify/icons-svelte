<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2ljocb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2ljocb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:filter-2" {...props}></Icon>
