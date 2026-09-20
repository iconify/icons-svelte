<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6smzk6xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6smzk6xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cake-remix" {...props}></Icon>
