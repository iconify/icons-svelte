<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pytu8sdic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pytu8sdic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:check-fill" {...props}></Icon>
