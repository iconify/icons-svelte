<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df5-fqb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="df5-fqb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gramophone" {...props}></Icon>
