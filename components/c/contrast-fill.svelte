<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltn6fn7xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltn6fn7xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contrast-fill" {...props}></Icon>
