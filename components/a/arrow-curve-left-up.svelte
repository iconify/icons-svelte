<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-q5gt73k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-q5gt73k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-left-up" {...props}></Icon>
