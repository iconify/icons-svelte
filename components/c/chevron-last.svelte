<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihrukyb8a.css';
import '../../css/b/bio4c781y.css';
import '../../css/u/u9zxaeb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihrukyb8a wm-k"/><path class="bio4c781y wm-k"/><path class="u9zxaeb-g wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevron-last" {...props}></Icon>
