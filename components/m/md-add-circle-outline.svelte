<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxds-kb_t.css';
import '../../css/m/moox_lvwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxds-kb_t"/><path class="moox_lvwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-add-circle-outline" {...props}></Icon>
