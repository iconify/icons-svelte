<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbwfv4bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbwfv4bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-down-right-lg" {...props}></Icon>
