<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp98f5wdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp98f5wdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-jmeter" {...props}></Icon>
