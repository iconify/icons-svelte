<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzp8_ubtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzp8_ubtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:dna-strand" {...props}></Icon>
