<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh1e9m4lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh1e9m4lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clipboard-list-outline" {...props}></Icon>
