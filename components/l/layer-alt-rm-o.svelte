<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb9vjab-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kb9vjab-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-alt-rm-o" {...props}></Icon>
