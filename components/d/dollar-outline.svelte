<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih1b-qb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih1b-qb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dollar-outline" {...props}></Icon>
