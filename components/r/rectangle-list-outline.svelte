<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lakha6bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lakha6bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:rectangle-list-outline" {...props}></Icon>
