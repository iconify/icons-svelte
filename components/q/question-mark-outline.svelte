<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u41r5aczw.css';
import '../../css/u/umyvzfuaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u41r5aczw"/><path class="umyvzfuaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-mark-outline" {...props}></Icon>
