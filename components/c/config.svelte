<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax27h5ulz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ax27h5ulz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:config" {...props}></Icon>
