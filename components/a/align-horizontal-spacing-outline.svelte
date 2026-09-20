<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhxhq9bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhxhq9bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizontal-spacing-outline" {...props}></Icon>
