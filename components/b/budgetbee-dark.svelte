<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sifh8-bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sifh8-bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budgetbee-dark" {...props}></Icon>
