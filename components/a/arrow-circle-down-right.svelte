<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6eirsb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="n6eirsb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-down-right" {...props}></Icon>
