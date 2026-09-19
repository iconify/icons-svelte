<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgdmlu84t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":896};
const content = `<path class="lgdmlu84t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:passwordalt" {...props}></Icon>
