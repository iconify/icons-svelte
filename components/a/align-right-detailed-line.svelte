<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd_-2rbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_-2rbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-detailed-line" {...props}></Icon>
