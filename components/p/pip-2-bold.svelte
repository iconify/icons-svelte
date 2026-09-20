<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9r7h8b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9r7h8b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pip-2-bold" {...props}></Icon>
