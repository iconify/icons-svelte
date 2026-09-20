<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulv5tg40c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ulv5tg40c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:delete-2-remix" {...props}></Icon>
