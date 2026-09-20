<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao4zormha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao4zormha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-right-circle-fill" {...props}></Icon>
