<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oon171yhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oon171yhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:exclaimation-triangle" {...props}></Icon>
