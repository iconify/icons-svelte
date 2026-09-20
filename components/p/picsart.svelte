<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adqyh6bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adqyh6bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:picsart" {...props}></Icon>
