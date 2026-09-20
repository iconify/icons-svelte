<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t19sicbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="t19sicbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:message-outline" {...props}></Icon>
