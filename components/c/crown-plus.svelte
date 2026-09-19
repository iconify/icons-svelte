<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/safu-vbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="safu-vbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:crown-plus" {...props}></Icon>
