<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snyhutb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="snyhutb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-circle-fill-20" {...props}></Icon>
