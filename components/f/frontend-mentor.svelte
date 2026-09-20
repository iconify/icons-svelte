<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqcft6fyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqcft6fyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:frontend-mentor" {...props}></Icon>
