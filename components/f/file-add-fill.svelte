<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq0e4bhuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq0e4bhuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:file-add-fill" {...props}></Icon>
