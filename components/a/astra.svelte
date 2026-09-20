<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2c3cy7nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2c3cy7nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:astra" {...props}></Icon>
