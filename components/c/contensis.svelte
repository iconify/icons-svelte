<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhj7tzbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhj7tzbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:contensis" {...props}></Icon>
