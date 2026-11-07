<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1omc9nvs.css';
import '../../css/u/unld3absx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1omc9nvs"/><path class="unld3absx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hanger-2-bold-duotone" {...props}></Icon>
