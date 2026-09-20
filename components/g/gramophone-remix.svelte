<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3of9q55g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n3of9q55g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gramophone-remix" {...props}></Icon>
