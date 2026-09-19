<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3tgzacne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g3tgzacne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-magnifying-glass-small" {...props}></Icon>
