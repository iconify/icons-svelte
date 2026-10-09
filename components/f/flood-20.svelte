<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xolj2c6gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xolj2c6gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flood-20" {...props}></Icon>
