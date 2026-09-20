<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erihghbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erihghbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:briefcase-24" {...props}></Icon>
