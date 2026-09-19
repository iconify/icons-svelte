<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o92t798_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o92t798_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-big-left" {...props}></Icon>
