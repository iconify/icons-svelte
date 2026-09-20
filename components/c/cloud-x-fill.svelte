<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idh2j0bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idh2j0bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-x-fill" {...props}></Icon>
