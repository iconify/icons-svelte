<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlwpi5b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwpi5b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-sharp" {...props}></Icon>
