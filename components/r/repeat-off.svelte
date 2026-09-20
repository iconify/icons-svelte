<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjsf23bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjsf23bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:repeat-off" {...props}></Icon>
