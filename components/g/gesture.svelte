<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2xfhibki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":392,"height":384};
const content = `<path class="g2xfhibki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:gesture" {...props}></Icon>
