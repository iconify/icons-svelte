<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_jjt_bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_jjt_bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrows-repeat-count-outline" {...props}></Icon>
