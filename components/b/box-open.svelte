<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez7i28aau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez7i28aau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:box-open" {...props}></Icon>
