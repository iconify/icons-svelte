<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5j55ub6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5j55ub6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloud-alt-02" {...props}></Icon>
