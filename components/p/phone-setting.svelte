<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmg7h7bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmg7h7bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-setting" {...props}></Icon>
