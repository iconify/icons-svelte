<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl6b8fzab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl6b8fzab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:moustache-remix" {...props}></Icon>
