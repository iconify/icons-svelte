<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_gtncfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y-_gtncfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:building-office-remix" {...props}></Icon>
