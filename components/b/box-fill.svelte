<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv8wbjnnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv8wbjnnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:box-fill" {...props}></Icon>
