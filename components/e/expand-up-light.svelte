<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdfgdtc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdfgdtc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-up-light" {...props}></Icon>
