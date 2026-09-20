<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em4j74_bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em4j74_bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mermaid" {...props}></Icon>
