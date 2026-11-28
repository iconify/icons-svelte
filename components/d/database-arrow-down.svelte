<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mehhvibxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mehhvibxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-arrow-down" {...props}></Icon>
