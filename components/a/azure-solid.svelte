<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aud51tbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aud51tbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:azure-solid" {...props}></Icon>
