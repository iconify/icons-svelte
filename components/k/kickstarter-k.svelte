<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzvwx7now.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="uzvwx7now"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:kickstarter-k" {...props}></Icon>
