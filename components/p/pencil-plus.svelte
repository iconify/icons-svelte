<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z41fqrahe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z41fqrahe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-plus" {...props}></Icon>
