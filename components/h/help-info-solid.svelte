<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu057eu8j.css';
import '../../css/q/qput4lnis.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 uu057eu8j"/><path class="clr-i-solid clr-i-solid-path-2 qput4lnis"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:help-info-solid" {...props}></Icon>
