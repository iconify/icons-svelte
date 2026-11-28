<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni8h9jbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni8h9jbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:credit-card-lock" {...props}></Icon>
