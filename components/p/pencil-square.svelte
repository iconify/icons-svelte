<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnixj-hrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lnixj-hrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:pencil-square" {...props}></Icon>
