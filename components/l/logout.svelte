<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icajq0lnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="icajq0lnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:logout" {...props}></Icon>
