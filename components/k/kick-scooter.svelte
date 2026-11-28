<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr6kczzpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr6kczzpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:kick-scooter" {...props}></Icon>
