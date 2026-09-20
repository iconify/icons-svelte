<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acxwcy58p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acxwcy58p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:progate" {...props}></Icon>
