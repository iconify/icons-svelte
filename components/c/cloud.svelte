<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb_kh08lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb_kh08lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:cloud" {...props}></Icon>
