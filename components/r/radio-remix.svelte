<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgth8dbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgth8dbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:radio-remix" {...props}></Icon>
