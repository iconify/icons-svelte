<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqfdsvbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqfdsvbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cloud-check" {...props}></Icon>
