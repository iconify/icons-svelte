<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlls_m23z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlls_m23z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-2-line" {...props}></Icon>
