<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gupi_7glt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gupi_7glt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:award-02" {...props}></Icon>
