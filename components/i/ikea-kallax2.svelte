<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny4c4nbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4c4nbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-kallax2" {...props}></Icon>
