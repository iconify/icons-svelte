<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea9f_abhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea9f_abhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bim" {...props}></Icon>
