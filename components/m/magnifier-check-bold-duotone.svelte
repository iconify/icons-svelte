<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwqarthoa.css';
import '../../css/f/frxk7_buw.css';
import '../../css/y/yrnx5ea_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwqarthoa"/><path class="frxk7_buw"/><path class="yrnx5ea_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-check-bold-duotone" {...props}></Icon>
