<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmv1at-2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmv1at-2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nox" {...props}></Icon>
