<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbj7tg7mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gbj7tg7mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:abbr-api" {...props}></Icon>
