<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1v3rzbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1v3rzbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:checklist-alt-fill" {...props}></Icon>
