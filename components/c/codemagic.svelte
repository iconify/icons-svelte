<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv0mcress.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv0mcress"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codemagic" {...props}></Icon>
