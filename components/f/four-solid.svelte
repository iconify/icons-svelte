<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvdo4znfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvdo4znfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:four-solid" {...props}></Icon>
