<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3nefdc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3nefdc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-square-fill" {...props}></Icon>
