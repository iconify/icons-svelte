<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6s_1f5fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6s_1f5fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-csv-outline" {...props}></Icon>
