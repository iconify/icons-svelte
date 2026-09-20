<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp3oeuzsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp3oeuzsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ieee" {...props}></Icon>
