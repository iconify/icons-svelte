<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dza_qqxed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dza_qqxed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:blogger-alt" {...props}></Icon>
