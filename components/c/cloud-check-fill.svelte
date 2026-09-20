<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q96z7vg-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q96z7vg-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-check-fill" {...props}></Icon>
