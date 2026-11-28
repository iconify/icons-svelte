<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muzy7pqmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muzy7pqmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:external-link-solid" {...props}></Icon>
