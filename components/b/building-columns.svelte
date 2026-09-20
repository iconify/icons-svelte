<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqqg_zbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqqg_zbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:building-columns" {...props}></Icon>
