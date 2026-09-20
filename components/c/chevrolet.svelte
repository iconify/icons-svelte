<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa4p4804g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa4p4804g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chevrolet" {...props}></Icon>
