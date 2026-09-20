<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk9k9sdqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk9k9sdqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:payoneer" {...props}></Icon>
