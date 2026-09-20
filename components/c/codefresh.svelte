<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv04xxbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv04xxbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codefresh" {...props}></Icon>
