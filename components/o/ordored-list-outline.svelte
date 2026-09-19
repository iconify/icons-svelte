<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne4kifgai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne4kifgai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:ordored-list-outline" {...props}></Icon>
