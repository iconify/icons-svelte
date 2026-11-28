<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alf14997c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="alf14997c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bring-to-front-thin" {...props}></Icon>
