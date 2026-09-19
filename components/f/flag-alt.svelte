<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6v9nvrha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6v9nvrha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:flag-alt" {...props}></Icon>
