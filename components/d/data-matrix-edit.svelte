<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh0q2jb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh0q2jb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:data-matrix-edit" {...props}></Icon>
