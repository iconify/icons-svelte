<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0-so7bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0-so7bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-notification-remix" {...props}></Icon>
