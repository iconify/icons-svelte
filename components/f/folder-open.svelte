<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imly4yk7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imly4yk7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-open" {...props}></Icon>
