<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woue8qb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woue8qb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-invoice-outline" {...props}></Icon>
