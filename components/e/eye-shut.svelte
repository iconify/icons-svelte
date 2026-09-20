<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcmho_b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcmho_b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-shut" {...props}></Icon>
