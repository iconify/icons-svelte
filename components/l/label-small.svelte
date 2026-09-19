<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-j9tdb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s-j9tdb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:label-small" {...props}></Icon>
