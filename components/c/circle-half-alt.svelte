<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxz_4f-mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxz_4f-mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-half-alt" {...props}></Icon>
