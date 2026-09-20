<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waljypbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waljypbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:face-mask-fill" {...props}></Icon>
