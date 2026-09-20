<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx3mlpxzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx3mlpxzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:keyboard-remix" {...props}></Icon>
