<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpvrcy3ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpvrcy3ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-yen" {...props}></Icon>
