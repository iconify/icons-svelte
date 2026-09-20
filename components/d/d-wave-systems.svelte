<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kultw5tss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kultw5tss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:d-wave-systems" {...props}></Icon>
