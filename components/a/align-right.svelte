<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suc4dvluk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suc4dvluk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:align-right" {...props}></Icon>
