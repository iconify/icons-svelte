<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ybdh-6b.css';
import '../../css/u/utixu3psl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ybdh-6b"/><path class="utixu3psl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:racket-duotone" {...props}></Icon>
