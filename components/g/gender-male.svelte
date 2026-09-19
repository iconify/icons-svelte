<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poxw_gbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poxw_gbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gender-male" {...props}></Icon>
