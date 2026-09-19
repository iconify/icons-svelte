<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6k78tbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q6k78tbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:database-nut-hex" {...props}></Icon>
