<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjv_7_bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjv_7_bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:check-square-line" {...props}></Icon>
