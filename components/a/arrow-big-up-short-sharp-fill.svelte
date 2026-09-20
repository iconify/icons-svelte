<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-uzxbyzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-uzxbyzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-up-short-sharp-fill" {...props}></Icon>
