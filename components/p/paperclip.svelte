<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjy585wqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjy585wqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:paperclip" {...props}></Icon>
