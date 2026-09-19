<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7f8bcqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oz7f8bcqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:joomla" {...props}></Icon>
