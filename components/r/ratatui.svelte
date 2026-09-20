<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eng9nmbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eng9nmbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ratatui" {...props}></Icon>
