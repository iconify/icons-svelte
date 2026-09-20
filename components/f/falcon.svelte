<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb_w47var.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb_w47var"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:falcon" {...props}></Icon>
