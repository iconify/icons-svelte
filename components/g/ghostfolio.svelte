<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7t92ym8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7t92ym8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ghostfolio" {...props}></Icon>
