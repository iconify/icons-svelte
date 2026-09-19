<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6-nmp8oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-nmp8oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:do-undo-light" {...props}></Icon>
