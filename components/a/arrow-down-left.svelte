<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz0t0xciq.css';
import '../../css/u/umqjyb9su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz0t0xciq wm-k"/><path class="umqjyb9su wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-down-left" {...props}></Icon>
