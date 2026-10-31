<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4-1pgbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g4-1pgbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h5-16-solid" {...props}></Icon>
