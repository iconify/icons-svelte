<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbzieh18n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tbzieh18n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlearrowright" {...props}></Icon>
