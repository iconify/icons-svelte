<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae2ga7sat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae2ga7sat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:embarcadero" {...props}></Icon>
