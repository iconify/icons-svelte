<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2tt4mbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2tt4mbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lambda-solid" {...props}></Icon>
