<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plv2debfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plv2debfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:filezilla" {...props}></Icon>
