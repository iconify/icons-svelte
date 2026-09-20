<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atcf69bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atcf69bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:journal-multiple" {...props}></Icon>
