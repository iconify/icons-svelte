<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg1zjbckc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg1zjbckc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codementor" {...props}></Icon>
