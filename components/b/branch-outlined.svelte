<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upgwdk1vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upgwdk1vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:branch-outlined" {...props}></Icon>
