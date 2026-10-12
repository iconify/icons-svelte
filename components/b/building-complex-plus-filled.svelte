<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yismpnbbv.css';
import '../../css/p/pddla0b_d.css';
import '../../css/g/gcy3r1rbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path clip-rule="evenodd" class="pddla0b_d"/><path class="gcy3r1rbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:building-complex-plus-filled" {...props}></Icon>
