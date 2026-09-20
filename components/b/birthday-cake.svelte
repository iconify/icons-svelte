<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzvekvb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzvekvb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:birthday-cake" {...props}></Icon>
