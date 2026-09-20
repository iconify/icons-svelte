<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya6w0mbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ya6w0mbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-person-16" {...props}></Icon>
