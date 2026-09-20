<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqvwxvbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqvwxvbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avianca" {...props}></Icon>
