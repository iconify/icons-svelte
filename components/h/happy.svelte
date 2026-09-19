<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4dxqubtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4dxqubtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:happy" {...props}></Icon>
