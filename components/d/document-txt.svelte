<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggu5fgb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggu5fgb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-txt" {...props}></Icon>
