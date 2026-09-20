<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyl63ac_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyl63ac_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:igdb" {...props}></Icon>
