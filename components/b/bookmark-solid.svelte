<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-9dobn6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-9dobn6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bookmark-solid" {...props}></Icon>
