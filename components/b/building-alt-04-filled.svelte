<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2boa_bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2boa_bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:building-alt-04-filled" {...props}></Icon>
