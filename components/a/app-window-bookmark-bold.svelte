<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiajmhv2g.css';
import '../../css/l/l0nhtrb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiajmhv2g"/><path class="l0nhtrb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:app-window-bookmark-bold" {...props}></Icon>
