<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm1jq5bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1jq5bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:actions" {...props}></Icon>
