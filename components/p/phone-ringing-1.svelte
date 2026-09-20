<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgy6n9bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgy6n9bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-ringing-1" {...props}></Icon>
