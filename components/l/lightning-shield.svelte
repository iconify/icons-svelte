<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v64wwbc6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v64wwbc6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-shield" {...props}></Icon>
