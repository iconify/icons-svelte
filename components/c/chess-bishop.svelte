<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpj0e4q2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpj0e4q2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chess-bishop" {...props}></Icon>
