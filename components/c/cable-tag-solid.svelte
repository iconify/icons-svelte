<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he_05f72i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="he_05f72i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cable-tag-solid" {...props}></Icon>
