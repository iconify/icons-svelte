<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8w6stbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8w6stbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:conekta" {...props}></Icon>
