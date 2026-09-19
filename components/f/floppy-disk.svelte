<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awlbw9bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="awlbw9bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:floppy-disk" {...props}></Icon>
