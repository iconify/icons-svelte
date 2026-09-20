<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4qg15bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4qg15bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opennebula" {...props}></Icon>
