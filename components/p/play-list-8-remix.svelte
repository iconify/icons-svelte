<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icn85e4wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="icn85e4wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:play-list-8-remix" {...props}></Icon>
