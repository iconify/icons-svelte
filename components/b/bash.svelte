<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drrvdkb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drrvdkb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bash" {...props}></Icon>
