<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gff9ssbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gff9ssbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:expand-right" {...props}></Icon>
