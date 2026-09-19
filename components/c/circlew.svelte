<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brlp6dbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="brlp6dbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlew" {...props}></Icon>
