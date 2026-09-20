<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu9qfpjil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9qfpjil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:horizontal-align-left" {...props}></Icon>
