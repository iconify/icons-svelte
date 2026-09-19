<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhmi89caq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhmi89caq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:infinity" {...props}></Icon>
