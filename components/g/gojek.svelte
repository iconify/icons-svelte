<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jun3midhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jun3midhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gojek" {...props}></Icon>
