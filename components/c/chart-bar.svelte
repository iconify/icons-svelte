<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibr0sobfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibr0sobfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chart-bar" {...props}></Icon>
