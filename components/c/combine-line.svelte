<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3fac04nz.css';
import '../../css/h/hj-hvqmvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3fac04nz"/><path class="hj-hvqmvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:combine-line" {...props}></Icon>
