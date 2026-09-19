<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdl1zucwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdl1zucwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-open-solid" {...props}></Icon>
