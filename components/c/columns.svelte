<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojz-7nhbw.css';
import '../../css/z/zr7zg75lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojz-7nhbw"/><path class="zr7zg75lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:columns" {...props}></Icon>
