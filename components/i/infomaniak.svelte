<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj8zdqb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj8zdqb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:infomaniak" {...props}></Icon>
