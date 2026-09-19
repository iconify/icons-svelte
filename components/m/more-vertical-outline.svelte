<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_8bvqb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="more-vertical-outline"><path class="Vector t_8bvqb7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:more-vertical-outline" {...props}></Icon>
