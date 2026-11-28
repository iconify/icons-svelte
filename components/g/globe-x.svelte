<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o687n4b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o687n4b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:globe-x" {...props}></Icon>
