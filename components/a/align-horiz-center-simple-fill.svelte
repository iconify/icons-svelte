<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw0com05s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw0com05s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-horiz-center-simple-fill" {...props}></Icon>
