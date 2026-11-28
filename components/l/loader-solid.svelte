<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs7fe0a1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs7fe0a1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:loader-solid" {...props}></Icon>
