<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnpfulbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnpfulbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:collapse-outline" {...props}></Icon>
