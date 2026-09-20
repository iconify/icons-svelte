<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2e82lb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2e82lb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:private-division" {...props}></Icon>
