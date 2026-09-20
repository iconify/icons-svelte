<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqy7ssh9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqy7ssh9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bones-outline" {...props}></Icon>
