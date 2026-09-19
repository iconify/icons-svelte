<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml0qg9bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="ml0qg9bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bell-alt" {...props}></Icon>
