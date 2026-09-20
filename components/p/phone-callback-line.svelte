<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjfl4gbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjfl4gbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-callback-line" {...props}></Icon>
