<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/absnrrb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="absnrrb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:attribution-remix" {...props}></Icon>
