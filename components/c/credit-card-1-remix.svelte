<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtmg25neu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qtmg25neu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:credit-card-1-remix" {...props}></Icon>
