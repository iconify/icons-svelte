<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubp6vsclr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ubp6vsclr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-synchronize-disable-remix" {...props}></Icon>
