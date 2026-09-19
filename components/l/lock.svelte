<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzxo1rbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzxo1rbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:lock" {...props}></Icon>
