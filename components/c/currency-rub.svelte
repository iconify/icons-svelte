<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpav7h32m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpav7h32m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-rub" {...props}></Icon>
