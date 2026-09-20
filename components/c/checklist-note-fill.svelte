<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1pgs7_hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1pgs7_hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:checklist-note-fill" {...props}></Icon>
