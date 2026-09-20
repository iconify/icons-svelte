<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkmw8b3ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkmw8b3ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lightning-alt-light" {...props}></Icon>
