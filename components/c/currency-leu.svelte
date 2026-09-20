<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvpk0lwda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvpk0lwda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-leu" {...props}></Icon>
