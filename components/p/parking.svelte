<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzz1z6ryv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzz1z6ryv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:parking" {...props}></Icon>
