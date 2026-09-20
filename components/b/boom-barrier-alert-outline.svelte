<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlo08zxww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlo08zxww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boom-barrier-alert-outline" {...props}></Icon>
