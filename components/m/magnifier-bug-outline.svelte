<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abtab-k7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abtab-k7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-bug-outline" {...props}></Icon>
