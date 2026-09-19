<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6tp-6btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6tp-6btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid-19-virus-4" {...props}></Icon>
