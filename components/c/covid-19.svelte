<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3m30c74w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3m30c74w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:covid-19" {...props}></Icon>
