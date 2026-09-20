<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqj_zryfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqj_zryfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:clock" {...props}></Icon>
