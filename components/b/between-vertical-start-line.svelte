<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmz_29bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmz_29bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:between-vertical-start-line" {...props}></Icon>
