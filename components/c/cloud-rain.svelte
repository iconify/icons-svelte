<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xits50bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xits50bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:cloud-rain" {...props}></Icon>
