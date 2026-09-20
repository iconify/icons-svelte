<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixxc27uve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixxc27uve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book" {...props}></Icon>
