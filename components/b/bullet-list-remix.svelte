<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_-izf01l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_-izf01l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bullet-list-remix" {...props}></Icon>
