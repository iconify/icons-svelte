<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm6fp7b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm6fp7b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pocket" {...props}></Icon>
