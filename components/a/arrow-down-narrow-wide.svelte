<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa9u5v4ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa9u5v4ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-narrow-wide" {...props}></Icon>
