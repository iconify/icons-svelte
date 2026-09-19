<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igi-6tbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igi-6tbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrows-repeat-outline" {...props}></Icon>
