<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_pz8lrtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_pz8lrtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:not-element-of-filled" {...props}></Icon>
