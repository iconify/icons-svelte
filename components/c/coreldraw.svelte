<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwenk5bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwenk5bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coreldraw" {...props}></Icon>
