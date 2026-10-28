<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu9somb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9somb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:border" {...props}></Icon>
