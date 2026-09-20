<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdjeycbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdjeycbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-left-fill" {...props}></Icon>
