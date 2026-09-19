<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_7gtnktk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n_7gtnktk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:menu-alt-3" {...props}></Icon>
