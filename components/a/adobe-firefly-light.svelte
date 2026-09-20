<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-jap0buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-jap0buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-firefly-light" {...props}></Icon>
