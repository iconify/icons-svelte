<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk1v-uboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yk1v-uboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-checks-20" {...props}></Icon>
