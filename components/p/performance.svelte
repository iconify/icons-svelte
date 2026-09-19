<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbz0a5b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbz0a5b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:performance" {...props}></Icon>
