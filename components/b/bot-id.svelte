<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d07qm6b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d07qm6b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bot-id" {...props}></Icon>
