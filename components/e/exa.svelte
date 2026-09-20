<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au8fi6b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="au8fi6b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:exa" {...props}></Icon>
