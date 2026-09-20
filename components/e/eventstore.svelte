<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nemmw3bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nemmw3bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eventstore" {...props}></Icon>
