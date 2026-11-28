<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izz6ghbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izz6ghbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-code-lock" {...props}></Icon>
